<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bnh0gv09x.css';
import '../../css/s/s-8e16bxy.css';
import '../../css/p/plg_eihxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bnh0gv09x"/><path class="s-8e16bxy"/><path clip-rule="evenodd" class="plg_eihxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:lock-open" /></template>
