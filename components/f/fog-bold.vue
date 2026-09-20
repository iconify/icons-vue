<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucnfbmfrx.css';
import '../../css/k/k5227db7l.css';
import '../../css/j/jwg3u8mon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucnfbmfrx"/><path class="k5227db7l"/><path class="jwg3u8mon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-bold" /></template>
