<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_dxl-1rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_dxl-1rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:code-block-fill-round" /></template>
