<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eixhrfb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="eixhrfb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-bar-1" /></template>
