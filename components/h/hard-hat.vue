<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k13rehn4f.css';
import '../../css/l/l1-9_tb1s.css';
import '../../css/d/dru2d75ul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k13rehn4f"/><path class="l1-9_tb1s"/><path class="dru2d75ul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hard-hat" /></template>
