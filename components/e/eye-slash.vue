<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u_cglrb8o.css';
import '../../css/z/ztzwvfbwf.css';
import '../../css/s/sfkx2xqaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="u_cglrb8o"/><path class="ztzwvfbwf"/><path class="sfkx2xqaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:eye-slash" /></template>
