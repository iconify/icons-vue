<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvzi1b8fa.css';
import '../../css/z/zy7040bus.css';
import '../../css/s/syhtlqbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="kvzi1b8fa"/><path class="zy7040bus"/><path class="syhtlqbrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart-duotone" /></template>
