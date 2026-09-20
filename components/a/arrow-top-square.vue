<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuqqggich.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuqqggich"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-top-square" /></template>
