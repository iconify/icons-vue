<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/waj2sm3ma.css';
import '../../css/g/g7vw0fb-l.css';
import '../../css/l/lpsbhjbjv.css';
import '../../css/r/ratx3zrrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="waj2sm3ma"/><path class="g7vw0fb-l"/><path clip-rule="evenodd" class="lpsbhjbjv"/><path class="ratx3zrrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:life-ring-duo" /></template>
