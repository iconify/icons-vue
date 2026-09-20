<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a2kliubwi.css';
import '../../css/n/n7_idhb2y.css';
import '../../css/g/gri8csbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a2kliubwi"/><path clip-rule="evenodd" class="n7_idhb2y"/><path clip-rule="evenodd" class="gri8csbwd"/><path clip-rule="evenodd" class="n7_idhb2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:house-bold" /></template>
