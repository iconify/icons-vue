<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/czeiw6b4w.css';
import '../../css/u/u1ptbhbni.css';
import '../../css/s/sfrj7abtj.css';
import '../../css/s/shp0ei0kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="czeiw6b4w"/><path class="u1ptbhbni"/><path class="sfrj7abtj"/><path class="shp0ei0kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-linear" /></template>
