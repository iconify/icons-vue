<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/odedu7bbc.css';
import '../../css/b/bxjv56brc.css';
import '../../css/t/t83hz6hkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="odedu7bbc wm-deco"/><path class="bxjv56brc wm-deco"/><path class="t83hz6hkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:command-blueprint" /></template>
