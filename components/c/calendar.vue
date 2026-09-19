<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a6f6n8r8g.css';
import '../../css/f/fbq_esbeu.css';
import '../../css/i/ia4tklbjm.css';
import '../../css/s/sue_o3bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="a6f6n8r8g"/><path class="fbq_esbeu"/><path class="ia4tklbjm"/><path class="sue_o3bci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:calendar" /></template>
