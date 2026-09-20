<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/az7hstbmu.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/a/akry8ac1d.css';
import '../../css/q/qmnpc1bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="az7hstbmu"/><g class="ij2x_72vy"><path class="akry8ac1d"/><circle class="qmnpc1bre"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:kissing-face-with-closed-eyes" /></template>
