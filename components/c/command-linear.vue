<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xmvx9bbmd.css';
import '../../css/w/w_9u0rbob.css';
import '../../css/m/mg9xohbul.css';
import '../../css/y/y8y0m0wuw.css';
import '../../css/l/lf0aqebqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xmvx9bbmd"/><path class="w_9u0rbob"/><path class="mg9xohbul"/><path class="y8y0m0wuw"/><path class="lf0aqebqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:command-linear" /></template>
