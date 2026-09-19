<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mlmxd1bpe.css';
import '../../css/l/lqsj7i-8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="mlmxd1bpe"/><path class="lqsj7i-8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:comment-unresolved-compact" /></template>
