<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gro5h1bir.css';
import '../../css/e/ew18oib6k.css';
import '../../css/e/ez0_tuu0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gro5h1bir"/><path clip-rule="evenodd" class="ew18oib6k"/><path class="ez0_tuu0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hiking2-duotone" /></template>
