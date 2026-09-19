<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcc50sb7a.css';
import '../../css/o/od2-gdbso.css';
import '../../css/e/esc0vsbcl.css';
import '../../css/v/vc-7i1ihb.css';
import '../../css/g/gj5k14bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wcc50sb7a"><rect class="od2-gdbso"/><rect class="esc0vsbcl"/><rect class="vc-7i1ihb"/><rect class="gj5k14bhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ellipsis-square-bold" /></template>
