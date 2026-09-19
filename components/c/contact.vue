<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vupjzmmpw.css';
import '../../css/t/tpe31d3ts.css';
import '../../css/h/hi0hwccqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vupjzmmpw"/><path class="tpe31d3ts"/><path class="hi0hwccqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:contact" /></template>
