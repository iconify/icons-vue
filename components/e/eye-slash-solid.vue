<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/z1y8b68qt.css';
import '../../css/c/cg7m802ly.css';
import '../../css/c/czoppacab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="z1y8b68qt"/><path class="cg7m802ly"/><path class="czoppacab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:eye-slash-solid" /></template>
