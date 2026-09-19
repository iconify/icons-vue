<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b1znrzx2a.css';
import '../../css/i/i3dorvb1g.css';
import '../../css/h/h6k4ikgxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b1znrzx2a"/><path clip-rule="evenodd" class="i3dorvb1g"/><path clip-rule="evenodd" class="h6k4ikgxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:boxing-glove" /></template>
