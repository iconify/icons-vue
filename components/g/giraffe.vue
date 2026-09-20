<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcxl47p1u.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/kyle7dbca.css';
import '../../css/j/js3pfvnsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fcxl47p1u"/><g class="ij2x_72vy"><path class="kyle7dbca"/><path class="js3pfvnsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:giraffe" /></template>
