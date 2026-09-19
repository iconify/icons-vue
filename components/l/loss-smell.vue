<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/glmqoxo2g.css';
import '../../css/t/tgi27dstf.css';
import '../../css/b/bs4c_4bsg.css';
import '../../css/q/q8p-vyb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="glmqoxo2g"/><path class="tgi27dstf"/><path clip-rule="evenodd" class="bs4c_4bsg"/><path class="q8p-vyb-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:loss-smell" /></template>
