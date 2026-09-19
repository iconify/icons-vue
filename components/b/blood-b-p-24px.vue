<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d6mo-un_y.css';
import '../../css/s/so_z8yfrn.css';
import '../../css/i/ixjaemx-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d6mo-un_y"/><path class="so_z8yfrn"/><path clip-rule="evenodd" class="ixjaemx-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-b-p-24px" /></template>
