<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rouiqnbvi.css';
import '../../css/l/lxa7bxwkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":33};
const content = `<g class="cuyn6tgcc"><path class="rouiqnbvi"/><path class="lxa7bxwkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:keycap-5" /></template>
