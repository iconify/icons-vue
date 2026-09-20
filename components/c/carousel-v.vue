<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uwa3mixdc.css';
import '../../css/a/a3mjwzvtg.css';
import '../../css/v/vi6r83tsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uwa3mixdc"/><path clip-rule="evenodd" class="a3mjwzvtg"/><path class="vi6r83tsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:carousel-v" /></template>
