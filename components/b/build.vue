<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pytq4bb0c.css';
import '../../css/v/vtc4ipbzp.css';
import '../../css/n/neygi1gkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="pytq4bb0c"/><path class="vtc4ipbzp"/><path class="neygi1gkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:build" /></template>
