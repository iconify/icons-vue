<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dsq17kvgv.css';
import '../../css/l/lvzj-jbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dsq17kvgv"/><path class="lvzj-jbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-dot-compact" /></template>
