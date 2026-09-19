<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wstva3b-l.css';
import '../../css/l/lnwbmf5ky.css';
import '../../css/o/ory6bvb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wstva3b-l"/><path clip-rule="evenodd" class="lnwbmf5ky"/><path class="ory6bvb6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:internet" /></template>
