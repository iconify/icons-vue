<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-ii8ac4d.css';
import '../../css/y/y0mw4ibgt.css';
import '../../css/i/im1hkobej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-ii8ac4d"/><path class="y0mw4ibgt"/><path class="im1hkobej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-minimalistic-broken" /></template>
