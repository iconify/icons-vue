<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edrlosohl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edrlosohl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:crop-7-5-filled" /></template>
