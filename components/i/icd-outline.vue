<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/otw5jg97e.css';
import '../../css/k/kcy22cc0q.css';
import '../../css/v/vfc_tmbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="otw5jg97e"/><path clip-rule="evenodd" class="kcy22cc0q"/><path clip-rule="evenodd" class="vfc_tmbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:icd-outline" /></template>
