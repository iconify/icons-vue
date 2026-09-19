<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/plj3cxbsw.css';
import '../../css/w/wg6qfxr2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="plj3cxbsw"/><path clip-rule="evenodd" class="wg6qfxr2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-circle-16-solid" /></template>
