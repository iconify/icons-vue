<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jgrtmnhmi.css';
import '../../css/x/x2xkjsa7t.css';
import '../../css/d/dw-bckwxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jgrtmnhmi"/><path class="x2xkjsa7t"/><path class="dw-bckwxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-pin" /></template>
