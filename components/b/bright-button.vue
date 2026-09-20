<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu85lyb9a.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/o-mn23hdo.css';
import '../../css/m/mtmqpmbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="fu85lyb9a"/><g class="ij2x_72vy"><circle class="o-mn23hdo"/><path class="mtmqpmbwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bright-button" /></template>
