<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q_vbzsbjb.css';
import '../../css/a/aykchpjie.css';
import '../../css/a/a-l4vyfjm.css';
import '../../css/u/ub0zacarc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="q_vbzsbjb"/><path clip-rule="evenodd" class="aykchpjie"/><path class="a-l4vyfjm"/><path clip-rule="evenodd" class="ub0zacarc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:camera" /></template>
