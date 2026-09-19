<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o1ff0s1ob.css';
import '../../css/c/cj6u56b5f.css';
import '../../css/r/rj5c37bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="o1ff0s1ob"/><path class="cj6u56b5f"/><path class="rj5c37bgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hospital" /></template>
