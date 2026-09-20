<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i0flq-qyx.css';
import '../../css/v/vvkghsb8y.css';
import '../../css/z/z4ahkzb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i0flq-qyx"/><path class="vvkghsb8y"/><path class="z4ahkzb1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-question-mark" /></template>
