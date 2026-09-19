<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x2xvw4bpz.css';
import '../../css/c/cwjg7g3za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="x2xvw4bpz"/><path clip-rule="evenodd" class="cwjg7g3za"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blister-pills-oval-x162x-outline" /></template>
