<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cq3f2yo5h.css';
import '../../css/h/h_-ew6blk.css';
import '../../css/o/orz_9qkrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cq3f2yo5h"/><path clip-rule="evenodd" class="h_-ew6blk"/><path class="orz_9qkrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chat-round-call-duotone" /></template>
