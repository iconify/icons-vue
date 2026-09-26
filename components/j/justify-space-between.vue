<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cmhb2q1wl.css';
import '../../css/l/lsg8msbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cmhb2q1wl"/><path vector-effect="non-scaling-stroke" class="lsg8msbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:justify-space-between" /></template>
