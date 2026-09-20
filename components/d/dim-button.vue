<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/larysibsv.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/dop23ibmn.css';
import '../../css/t/tkfk-sbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="larysibsv"/><g class="ij2x_72vy"><circle class="dop23ibmn"/><path class="tkfk-sbea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dim-button" /></template>
