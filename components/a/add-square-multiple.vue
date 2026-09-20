<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/vmchpqbpy.css';
import '../../css/i/ideagcboz.css';
import '../../css/e/e5x2664gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vmchpqbpy"/><rect class="ideagcboz"/><path class="e5x2664gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:add-square-multiple" /></template>
