<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/e35pomtwe.css';
import '../../css/v/vd6q9kbib.css';
import '../../css/m/mrj31bc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e35pomtwe"/><path class="vd6q9kbib"/><path class="mrj31bc2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter-tick" /></template>
