<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pdoa3kqmg.css';
import '../../css/g/g2l8iqnuw.css';
import '../../css/o/or9nmxbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="pdoa3kqmg"/><path class="g2l8iqnuw"/><path class="or9nmxbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:coin" /></template>
