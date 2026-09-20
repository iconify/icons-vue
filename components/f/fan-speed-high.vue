<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3io2-glk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3io2-glk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-speed-high" /></template>
