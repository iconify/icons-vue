<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1bbndrsh.css';
import '../../css/r/r2avjyb5n.css';
import '../../css/o/oosdw9lib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="j1bbndrsh"><path class="r2avjyb5n"/><path class="oosdw9lib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-double-outline" /></template>
