<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qxwgb7p4b.css';
import '../../css/j/j4on_51kq.css';
import '../../css/d/du1p5sbuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qxwgb7p4b"/><path class="j4on_51kq"/><path clip-rule="evenodd" class="du1p5sbuh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ecmo-outline-24px" /></template>
