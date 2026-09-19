<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/scj6e7j8j.css';
import '../../css/o/obezgrllk.css';
import '../../css/z/zs0uyebvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="scj6e7j8j"/><path class="obezgrllk"/><path clip-rule="evenodd" class="zs0uyebvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:enzyme-outline-24px" /></template>
