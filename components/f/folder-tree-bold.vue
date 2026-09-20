<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f3gj-6bzn.css';
import '../../css/d/d2paqerlk.css';
import '../../css/k/kk4e1dben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f3gj-6bzn"/><path class="d2paqerlk"/><path class="kk4e1dben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-tree-bold" /></template>
