<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hr4pu4blu.css';
import '../../css/p/p5g5pxbqg.css';
import '../../css/k/k3eo_eo4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr4pu4blu"/><path class="p5g5pxbqg"/><path class="k3eo_eo4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:data2-filled" /></template>
