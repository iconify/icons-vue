<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/n/n68pnzbbs.css';
import '../../css/u/usc9pbclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="n68pnzbbs"/><path class="usc9pbclp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-holding-heart" /></template>
