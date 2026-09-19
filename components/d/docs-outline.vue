<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1bbndrsh.css';
import '../../css/u/ullp8vaok.css';
import '../../css/n/nx2c618gt.css';
import '../../css/d/douhlrken.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="ullp8vaok"/><path class="nx2c618gt"/><path class="douhlrken"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:docs-outline" /></template>
