<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ap1d5ab4f.css';
import '../../css/r/rr4yu8s3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ap1d5ab4f"/><path clip-rule="evenodd" class="rr4yu8s3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark3" /></template>
