<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__s2g6zp.css';
import '../../css/f/f4sd56baf.css';
import '../../css/b/bbhoyd3dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="f4sd56baf"/><path class="bbhoyd3dh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:battery-charge-bold" /></template>
