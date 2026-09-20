<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kvclpxbgj.css';
import '../../css/k/ka62jfb8e.css';
import '../../css/p/poocn6j4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kvclpxbgj"/><path clip-rule="evenodd" class="ka62jfb8e"/><path class="poocn6j4k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop-download" /></template>
