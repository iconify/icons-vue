<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj_j01b-n.css';
import '../../css/k/k99pi4o6z.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/khaum3bxk.css';
import '../../css/g/go94mvb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="oj_j01b-n"/><path class="k99pi4o6z"/><g class="ij2x_72vy"><path class="khaum3bxk"/><path class="go94mvb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:hedgehog" /></template>
