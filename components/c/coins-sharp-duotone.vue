<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/j41a42nnh.css';
import '../../css/y/y5hju585n.css';
import '../../css/r/rkjqeacdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j41a42nnh"/><path clip-rule="evenodd" class="y5hju585n"/><path class="rkjqeacdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:coins-sharp-duotone" /></template>
