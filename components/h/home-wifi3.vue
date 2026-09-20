<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aoru-1c7c.css';
import '../../css/x/xq1bxcbka.css';
import '../../css/z/z4_iucblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aoru-1c7c"/><path class="xq1bxcbka"/><path clip-rule="evenodd" class="z4_iucblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:home-wifi3" /></template>
