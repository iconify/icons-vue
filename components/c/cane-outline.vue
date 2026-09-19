<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w9wpg9cgy.css';
import '../../css/x/xyvolmu6b.css';
import '../../css/n/nnw93lbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w9wpg9cgy"/><path class="xyvolmu6b"/><path clip-rule="evenodd" class="nnw93lbbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cane-outline" /></template>
