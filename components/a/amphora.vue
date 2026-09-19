<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lcn5imzsu.css';
import '../../css/o/ocg5i7b2f.css';
import '../../css/w/w23rjnycg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lcn5imzsu"/><path class="ocg5i7b2f"/><path class="w23rjnycg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:amphora" /></template>
