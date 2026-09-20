<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/geji5ur7w.css';
import '../../css/t/tke_5wp7o.css';
import '../../css/k/kqzenpjvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="geji5ur7w"/><path clip-rule="evenodd" class="tke_5wp7o"/><path clip-rule="evenodd" class="kqzenpjvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bacteria" /></template>
