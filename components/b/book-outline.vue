<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/osmjh3u8s.css';
import '../../css/b/b2it0vylx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="osmjh3u8s"/><path clip-rule="evenodd" class="b2it0vylx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:book-outline" /></template>
