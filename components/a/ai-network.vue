<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/d/dvfl3fbbc.css';
import '../../css/q/q7oonn27c.css';
import '../../css/d/d02nshtjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dvfl3fbbc"/><path class="q7oonn27c"/><path class="d02nshtjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-network" /></template>
