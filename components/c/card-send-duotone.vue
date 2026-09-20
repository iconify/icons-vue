<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n2jxbkb8j.css';
import '../../css/d/dnyemccis.css';
import '../../css/z/zjapeywkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n2jxbkb8j"/><path clip-rule="evenodd" class="dnyemccis"/><path class="zjapeywkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-send-duotone" /></template>
