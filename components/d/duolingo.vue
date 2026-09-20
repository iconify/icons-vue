<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcacu8bzy.css';
import '../../css/d/d5mgwabbh.css';
import '../../css/t/t81c4t1xw.css';
import '../../css/m/mg3283bzi.css';
import '../../css/o/o2sta01bz.css';
import '../../css/p/p7mxrbcml.css';
import '../../css/m/map-tsfko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tcacu8bzy"/><path class="d5mgwabbh"/><path class="t81c4t1xw"/><path class="mg3283bzi"/><path class="o2sta01bz"/><path class="p7mxrbcml"/><path class="map-tsfko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:duolingo" /></template>
