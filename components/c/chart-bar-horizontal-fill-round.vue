<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfp_h_bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfp_h_bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-bar-horizontal-fill-round" /></template>
