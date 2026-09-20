<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t6a7bkb4b.css';
import '../../css/t/t4n5mvw8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t6a7bkb4b"/><path vector-effect="non-scaling-stroke" class="t4n5mvw8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:audio" /></template>
