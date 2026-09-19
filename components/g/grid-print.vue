<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/r/rdpoembmx.css';
import '../../css/y/yf2e2qbao.css';
import '../../css/c/c-k3z045a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><path class="rdpoembmx"/><path clip-rule="evenodd" class="yf2e2qbao"/></g><path clip-rule="evenodd" class="c-k3z045a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:grid-print" /></template>
