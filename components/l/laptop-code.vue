<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xb58bubnl.css';
import '../../css/k/ka62jfb8e.css';
import '../../css/p/pq3m40bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xb58bubnl"/><path clip-rule="evenodd" class="ka62jfb8e"/><path class="pq3m40bxc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop-code" /></template>
