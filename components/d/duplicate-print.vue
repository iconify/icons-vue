<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h2fzalbpg.css';
import '../../css/j/jfesrw_tv.css';
import '../../css/f/ftj9ogb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="h2fzalbpg"/><path clip-rule="evenodd" class="jfesrw_tv"/><path class="ftj9ogb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:duplicate-print" /></template>
