<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qax0en9df.css';
import '../../css/e/e7qg44ydn.css';
import '../../css/k/kyo4-ot9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qax0en9df"/><path clip-rule="evenodd" class="e7qg44ydn"/><path class="kyo4-ot9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cloud-meatball-solid" /></template>
