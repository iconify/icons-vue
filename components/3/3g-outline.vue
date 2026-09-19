<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hij1pb51c.css';
import '../../css/b/b06lz2bfp.css';
import '../../css/t/tjj8vhbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hij1pb51c"/><path class="b06lz2bfp"/><path clip-rule="evenodd" class="tjj8vhbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:3g-outline" /></template>
