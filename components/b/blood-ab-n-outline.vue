<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j852ylbcm.css';
import '../../css/n/n1004lbky.css';
import '../../css/y/ys3b370un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="j852ylbcm"/><path clip-rule="evenodd" class="n1004lbky"/><path class="ys3b370un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-ab-n-outline" /></template>
