<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsh9rtrrg.css';
import '../../css/p/pnm561ulh.css';
import '../../css/r/r10cmbc9l.css';
import '../../css/g/gyw-nbbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="tsh9rtrrg"><rect class="pnm561ulh"/><rect class="r10cmbc9l"/><rect class="gyw-nbbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:columns-3-bold" /></template>
