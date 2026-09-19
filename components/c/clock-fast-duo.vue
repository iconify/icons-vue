<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/njo-2mzrh.css';
import '../../css/s/saiuxqbjq.css';
import '../../css/t/t8e0g0b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="njo-2mzrh"/><path class="saiuxqbjq"/><path class="t8e0g0b1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:clock-fast-duo" /></template>
