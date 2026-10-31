<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o_gvckftk.css';
import '../../css/u/uhqi6hhrp.css';
import '../../css/x/x8mrpdb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o_gvckftk wm-k"/><path class="uhqi6hhrp wm-shine"/><path class="wm-shine x8mrpdb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:book-marked" /></template>
