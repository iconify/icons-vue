<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/y/y5u96sb9x.css';
import '../../css/z/zjhnhpypo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path class="y5u96sb9x"/><path clip-rule="evenodd" class="zjhnhpypo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-align-horizontal-solid" /></template>
