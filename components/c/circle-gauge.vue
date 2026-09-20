<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/ry8v7ffhn.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/x/xzx4xfb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ry8v7ffhn"/><circle class="h_tsn8bxt"/><path class="xzx4xfb6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:circle-gauge" /></template>
