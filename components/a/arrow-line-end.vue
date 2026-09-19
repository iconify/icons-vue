<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z3lzi1byl.css';
import '../../css/a/auji-xecj.css';
import '../../css/v/vupovj4do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="z3lzi1byl"/><path class="auji-xecj"/><path class="vupovj4do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrow-line-end" /></template>
