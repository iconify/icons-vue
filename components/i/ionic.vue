<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfnlz1bwm.css';
import '../../css/y/yvav3etyo.css';
import '../../css/k/kx7lj1yvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="jfnlz1bwm"><path class="yvav3etyo"/><circle class="kx7lj1yvv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ionic" /></template>
