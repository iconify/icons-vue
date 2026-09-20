<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x_90y3bpa.css';
import '../../css/j/jwj5s6brs.css';
import '../../css/h/hll003ogx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x_90y3bpa"/><path class="jwj5s6brs"/><path clip-rule="evenodd" class="hll003ogx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-triangle-outline" /></template>
