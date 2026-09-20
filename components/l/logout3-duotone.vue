<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zmd9tro5y.css';
import '../../css/x/xvka29bcn.css';
import '../../css/z/zf_ua80du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zmd9tro5y"/><path class="xvka29bcn"/><path clip-rule="evenodd" class="zf_ua80du"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:logout3-duotone" /></template>
