<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jw65pab4k.css';
import '../../css/n/n1004lbky.css';
import '../../css/y/ys3b370un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jw65pab4k"/><path clip-rule="evenodd" class="n1004lbky"/><path class="ys3b370un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-ab-n" /></template>
