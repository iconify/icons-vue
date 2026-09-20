<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nbicbbcfy.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bxw8ohblp.css';
import '../../css/l/lqwd9zr1i.css';
import '../../css/b/bethf461k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="nbicbbcfy"/><g transform="translate(2 2)" class="cuyn6tgcc"><circle class="bxw8ohblp"/><circle class="lqwd9zr1i"/><circle class="bethf461k"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:calendar-days" /></template>
