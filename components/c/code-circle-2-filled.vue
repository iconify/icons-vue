<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-c2jjncm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-c2jjncm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:code-circle-2-filled" /></template>
