<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r1xw7kb1y.css';
import '../../css/r/rrq076sgb.css';
import '../../css/w/wxytlubjr.css';
import '../../css/k/kspoj7vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r1xw7kb1y"/><path clip-rule="evenodd" class="rrq076sgb"/><path class="wxytlubjr"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:lock-closed-circle" /></template>
