<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/a/a8qmqgb6k.css';
import '../../css/t/t0fqmp0yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="a8qmqgb6k"/><path class="t0fqmp0yx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-pointer-sparkles-sharp" /></template>
