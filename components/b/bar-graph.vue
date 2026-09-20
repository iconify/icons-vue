<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/elns7ebwh.css';
import '../../css/w/w-_t-lb4p.css';
import '../../css/l/l_1wr2zvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elns7ebwh"/><rect class="w-_t-lb4p"/><rect class="l_1wr2zvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bar-graph" /></template>
