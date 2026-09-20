<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rn08x5brb.css';
import '../../css/p/pk2i_1x1h.css';
import '../../css/n/ngo4x72kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rn08x5brb"/><path clip-rule="evenodd" class="pk2i_1x1h"/><path class="ngo4x72kh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-emoji-bold" /></template>
