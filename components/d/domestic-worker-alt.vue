<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ixbft3bvx.css';
import '../../css/p/pe-vqcblg.css';
import '../../css/v/vm02urlpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ixbft3bvx"/><path clip-rule="evenodd" class="pe-vqcblg"/><path class="vm02urlpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:domestic-worker-alt" /></template>
