<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mh6shxbiv.css';
import '../../css/j/je5fosb6a.css';
import '../../css/b/bx2vp8bax.css';
import '../../css/h/h0o4n2hyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mh6shxbiv"/><path class="je5fosb6a"/><path class="bx2vp8bax"/><path class="h0o4n2hyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrows-exchange" /></template>
