<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p0til8bxh.css';
import '../../css/s/s8qdqwbpf.css';
import '../../css/m/m0u-b0o0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p0til8bxh"/><path class="s8qdqwbpf"/><path clip-rule="evenodd" class="m0u-b0o0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-receive-filled" /></template>
