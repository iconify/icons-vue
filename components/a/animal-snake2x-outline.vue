<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ejjbf4g2r.css';
import '../../css/d/dhd8s--ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ejjbf4g2r"/><path clip-rule="evenodd" class="dhd8s--ip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-snake2x-outline" /></template>
