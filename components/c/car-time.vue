<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/suft8gbjr.css';
import '../../css/i/i6mewxbcc.css';
import '../../css/q/q2qyt3beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suft8gbjr"/><circle class="i6mewxbcc"/><path class="q2qyt3beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:car-time" /></template>
