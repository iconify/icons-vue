<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/ikr4zbc5h.css';
import '../../css/r/rj5v1bbrm.css';
import '../../css/y/yvwyapbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ikr4zbc5h"/><rect transform="matrix(-1 0 0 1 19.75 7)" class="rj5v1bbrm"/><rect transform="matrix(-1 0 0 1 10.25 4.5)" class="yvwyapbau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:align-horizontal-centers" /></template>
