<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uluktcj_s.css';
import '../../css/c/ch0qgpbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<g class="cuyn6tgcc"><path class="uluktcj_s"/><path class="ch0qgpbmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:disqus" /></template>
