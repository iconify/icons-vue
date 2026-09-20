<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3azj_gbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3azj_gbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:artboard-2-fill" /></template>
