<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wrwywm8dv.css';
import '../../css/u/ucjoi-m7d.css';
import '../../css/g/gv8vpi07i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wrwywm8dv"/><path clip-rule="evenodd" class="ucjoi-m7d"/><path class="gv8vpi07i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-bracket-end-bold" /></template>
