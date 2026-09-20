<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5emv0box.css';
import '../../css/d/d4g-9tsgn.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/de-mnhbxx.css';
import '../../css/i/i79r_h0sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="j5emv0box"/><path class="d4g-9tsgn"/><g class="ij2x_72vy"><path class="de-mnhbxx"/><path class="i79r_h0sv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dragon" /></template>
