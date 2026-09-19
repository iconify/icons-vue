<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sto5bkbur.css';
import '../../css/s/sxiy_gize.css';
import '../../css/e/epswth33l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="sto5bkbur"><path class="sxiy_gize"/><path class="epswth33l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:arduino-wordmark" /></template>
