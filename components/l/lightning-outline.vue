<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/reh1alp-u.css';
import '../../css/l/l_08mx4se.css';
import '../../css/i/i6ynjwb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="reh1alp-u"/><path class="l_08mx4se"/><path clip-rule="evenodd" class="i6ynjwb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lightning-outline" /></template>
