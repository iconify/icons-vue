<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0r-2x1bp.css';
import '../../css/m/m7mjk89gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="f0r-2x1bp"/><path class="m7mjk89gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:esbuild" /></template>
