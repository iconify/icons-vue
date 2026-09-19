<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mvhue2bke.css';
import '../../css/f/f2ii2fbzk.css';
import '../../css/z/z--8wl3pt.css';
import '../../css/e/el36qo26z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mvhue2bke"/><path class="f2ii2fbzk"/><path clip-rule="evenodd" class="z--8wl3pt"/><path class="el36qo26z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:canoe-2" /></template>
