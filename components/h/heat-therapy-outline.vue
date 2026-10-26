<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i77f6iezr.css';
import '../../css/d/ddg2v8bix.css';
import '../../css/v/v0i5h5b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="i77f6iezr"/><path clip-rule="evenodd" class="ddg2v8bix"/><path class="v0i5h5b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:heat-therapy-outline" /></template>
