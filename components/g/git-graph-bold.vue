<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cx-byxm-k.css';
import '../../css/g/gtnoc3_rf.css';
import '../../css/s/sm4k1ettw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cx-byxm-k"/><path class="gtnoc3_rf"/><path clip-rule="evenodd" class="sm4k1ettw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-graph-bold" /></template>
