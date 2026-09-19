<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/av4gw518w.css';
import '../../css/f/fa6jpzb7g.css';
import '../../css/v/vcy3f8_9t.css';
import '../../css/v/vs29xyb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="av4gw518w"/><path class="fa6jpzb7g"/><path clip-rule="evenodd" class="vcy3f8_9t"/><path class="vs29xyb9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bell-remove-outline" /></template>
