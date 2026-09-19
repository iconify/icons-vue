<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/t/tdx90sbxu.css';
import '../../css/k/k4lc0qbsm.css';
import '../../css/t/t5kuevs6k.css';
import '../../css/s/ss-q8-bzy.css';
import '../../css/i/ilnzqemtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><rect class="tdx90sbxu"/><rect class="k4lc0qbsm"/></g><rect class="t5kuevs6k"/><path class="ss-q8-bzy"/><path clip-rule="evenodd" class="ilnzqemtd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:battery-print" /></template>
