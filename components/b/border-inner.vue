<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b478ysu_w.css';
import '../../css/i/i855i0nqt.css';
import '../../css/v/vztj0xbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="b478ysu_w"/><path class="i855i0nqt"/><path class="vztj0xbin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:border-inner" /></template>
