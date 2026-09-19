<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hjylen1rs.css';
import '../../css/h/hvd6d7brl.css';
import '../../css/w/walgkl0pe.css';
import '../../css/m/mcjgljl4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hjylen1rs"/><path clip-rule="evenodd" class="hvd6d7brl"/><path class="walgkl0pe"/><path clip-rule="evenodd" class="mcjgljl4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:gonorrhea-outline" /></template>
