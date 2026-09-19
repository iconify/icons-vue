<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/oxj5z9e-b.css';
import '../../css/t/ti0uovb4m.css';
import '../../css/y/y6yajw26h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oxj5z9e-b"/><path class="ti0uovb4m"/><path class="y6yajw26h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframes" /></template>
