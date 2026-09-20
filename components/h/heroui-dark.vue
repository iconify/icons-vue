<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s6154jvgb.css';
import '../../css/h/hb9fpsbpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":74,"height":74};
const content = `<g class="ft5dv1b6b"><path class="s6154jvgb"/><path class="hb9fpsbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:heroui-dark" /></template>
