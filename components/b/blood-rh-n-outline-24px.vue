<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r50ruyp5z.css';
import '../../css/f/fm0pxnbwp.css';
import '../../css/v/vqsfm7b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r50ruyp5z"/><path clip-rule="evenodd" class="fm0pxnbwp"/><path class="vqsfm7b3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-rh-n-outline-24px" /></template>
