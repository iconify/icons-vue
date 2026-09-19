<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uw5t6o7sg.css';
import '../../css/b/bgej-bcgz.css';
import '../../css/u/u2zzmjbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="uw5t6o7sg"/><path clip-rule="evenodd" class="bgej-bcgz"/><path class="u2zzmjbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:copy" /></template>
