<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y7y4rmcqj.css';
import '../../css/b/b7k4_bbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="y7y4rmcqj"/><path clip-rule="evenodd" class="b7k4_bbom"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-cow-outline" /></template>
