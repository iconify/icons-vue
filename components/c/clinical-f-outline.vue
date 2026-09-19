<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cw1r4wl-u.css';
import '../../css/d/djzed1b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="cw1r4wl-u"/><path clip-rule="evenodd" class="djzed1b0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:clinical-f-outline" /></template>
