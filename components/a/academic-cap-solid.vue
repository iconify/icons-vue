<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ck9a2y9bt.css';
import '../../css/h/hyklb6qnw.css';
import '../../css/t/tq2ype9_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ck9a2y9bt"/><path class="hyklb6qnw"/><path class="tq2ype9_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:academic-cap-solid" /></template>
