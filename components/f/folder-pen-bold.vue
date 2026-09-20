<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h0lv2dbka.css';
import '../../css/d/dwhrthbwy.css';
import '../../css/j/jxgl27bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h0lv2dbka"/><path class="dwhrthbwy"/><path clip-rule="evenodd" class="jxgl27bqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-pen-bold" /></template>
