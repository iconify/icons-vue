<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol1qgland.css';
import '../../css/k/k0rioybmz.css';
import '../../css/k/ktabidctm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ol1qgland"><path class="k0rioybmz"/><path class="ktabidctm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:add-pic" /></template>
