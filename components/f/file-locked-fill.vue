<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e63dy304p.css';
import '../../css/s/svi8x9byo.css';
import '../../css/c/cgkpg5bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e63dy304p"/><path class="svi8x9byo"/><path clip-rule="evenodd" class="cgkpg5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-locked-fill" /></template>
