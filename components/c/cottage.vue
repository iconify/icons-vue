<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bos0j4biy.css';
import '../../css/r/rs-d_y_0o.css';
import '../../css/j/joxvtybff.css';
import '../../css/f/fcl75_otk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bos0j4biy"/><circle class="rs-d_y_0o"/><path class="joxvtybff"/><path class="fcl75_otk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cottage" /></template>
