<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xn4aaqbkb.css';
import '../../css/e/eyjrvqbsq.css';
import '../../css/z/zs55ho22r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="xn4aaqbkb"/><path class="eyjrvqbsq"/><path class="zs55ho22r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:camera-reels-fill" /></template>
