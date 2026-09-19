<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/syc0r02fb.css';
import '../../css/i/idpfg-7ly.css';
import '../../css/g/goyq6_8eq.css';
import '../../css/i/iw56heams.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="syc0r02fb"/><path class="idpfg-7ly"/><path class="goyq6_8eq"/><path class="iw56heams"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:envelope-open-duo" /></template>
