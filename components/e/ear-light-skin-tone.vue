<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzrff5bem.css';
import '../../css/o/ogq8t8zoi.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/t/ty0jp0byr.css';
import '../../css/z/zyiv9wvjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xzrff5bem"/><path class="ogq8t8zoi"/><g class="ij2x_72vy"><path class="ty0jp0byr"/><path class="zyiv9wvjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ear-light-skin-tone" /></template>
