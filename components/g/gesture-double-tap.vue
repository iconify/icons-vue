<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtr5x3_vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtr5x3_vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-double-tap" /></template>
