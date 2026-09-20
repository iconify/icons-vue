<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pd3bayrqp.css';
import '../../css/c/cuh4qccmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><rect class="pd3bayrqp"/><path class="cuh4qccmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:apollodotio" /></template>
