<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqlpajbrm.css';
import '../../css/l/l_82l62bb.css';
import '../../css/f/fzg7edc3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dqlpajbrm"/><path class="l_82l62bb"/><path class="fzg7edc3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:database-bold" /></template>
