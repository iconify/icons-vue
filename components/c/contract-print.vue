<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/git7l28wk.css';
import '../../css/n/nqnhmqeui.css';
import '../../css/u/u3ok_i7gk.css';
import '../../css/m/maprmj0tb.css';
import '../../css/u/u_3o3ug4w.css';
import '../../css/p/p3gd-mbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="git7l28wk"/><path class="nqnhmqeui"/><path class="u3ok_i7gk"/><path class="maprmj0tb"/><path class="u_3o3ug4w"/><path class="p3gd-mbhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:contract-print" /></template>
