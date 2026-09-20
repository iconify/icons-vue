<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/ja_ybdb3r.css';
import '../../css/j/j7dyzlxlx.css';
import '../../css/r/ryhenzbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ja_ybdb3r"/><path class="j7dyzlxlx"/><path clip-rule="evenodd" class="ryhenzbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:car-outline" /></template>
