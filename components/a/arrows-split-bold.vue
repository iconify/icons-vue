<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j42smtb5k.css';
import '../../css/j/juqffaboa.css';
import '../../css/r/rj0i6trac.css';
import '../../css/k/kc-5kvxmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="j42smtb5k"/><path class="juqffaboa"/><path class="rj0i6trac"/><path class="kc-5kvxmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrows-split-bold" /></template>
