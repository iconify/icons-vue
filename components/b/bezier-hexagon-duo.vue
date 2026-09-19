<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/urue2_g_v.css';
import '../../css/a/acuj0xb6z.css';
import '../../css/t/th2izabht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="urue2_g_v"/><path class="acuj0xb6z"/><path class="th2izabht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-hexagon-duo" /></template>
