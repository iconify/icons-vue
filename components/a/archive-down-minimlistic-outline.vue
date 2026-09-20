<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydol6mbyu.css';
import '../../css/r/r8h9qdcac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydol6mbyu"/><path clip-rule="evenodd" class="r8h9qdcac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-down-minimlistic-outline" /></template>
