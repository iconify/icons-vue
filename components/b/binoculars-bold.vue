<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h_qzm70hz.css';
import '../../css/v/vtr87b2ik.css';
import '../../css/c/cllgogb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h_qzm70hz"/><path class="vtr87b2ik"/><path clip-rule="evenodd" class="cllgogb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-bold" /></template>
