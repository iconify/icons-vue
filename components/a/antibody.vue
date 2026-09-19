<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bj3ijhgye.css';
import '../../css/x/x72vtmf2a.css';
import '../../css/k/kt_6d8b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="bj3ijhgye"/><path class="x72vtmf2a"/><path class="kt_6d8b9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:antibody" /></template>
