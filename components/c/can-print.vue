<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ewxr_5mgv.css';
import '../../css/v/v7k1qo54j.css';
import '../../css/d/dgb86uv6c.css';
import '../../css/o/o8rtmh1bo.css';
import '../../css/h/h972qfbbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ewxr_5mgv"/><path clip-rule="evenodd" class="v7k1qo54j"/><path clip-rule="evenodd" class="dgb86uv6c"/><path class="o8rtmh1bo"/><path class="h972qfbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:can-print" /></template>
