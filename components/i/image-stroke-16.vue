<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/p/ph1s97tzl.css';
import '../../css/y/yh4fy_bgb.css';
import '../../css/t/tpngvrbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><rect class="ph1s97tzl"/><path class="yh4fy_bgb"/></g><circle class="tpngvrbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:image-stroke-16" /></template>
