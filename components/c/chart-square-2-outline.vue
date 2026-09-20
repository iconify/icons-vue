<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qq3jwzbiv.css';
import '../../css/l/l_rtxu4wa.css';
import '../../css/i/ia1mkhbft.css';
import '../../css/u/u5bqo67kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qq3jwzbiv"/><path class="l_rtxu4wa"/><path class="ia1mkhbft"/><path clip-rule="evenodd" class="u5bqo67kp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-square-2-outline" /></template>
