<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo_l9zrur.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mjqsc3bcv.css';
import '../../css/a/as1-0ybuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="yo_l9zrur"/><g class="ij2x_72vy"><path class="mjqsc3bcv"/><circle class="as1-0ybuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:add-button" /></template>
