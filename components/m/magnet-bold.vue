<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u6ujfib6g.css';
import '../../css/l/la5t6nb-e.css';
import '../../css/t/tt7e65bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u6ujfib6g"/><path class="la5t6nb-e"/><path class="tt7e65bxw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnet-bold" /></template>
