<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f5k9ujbll.css';
import '../../css/d/dj61l2blf.css';
import '../../css/s/s2qm3rbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f5k9ujbll"/><path clip-rule="evenodd" class="dj61l2blf"/><path class="s2qm3rbjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-outline" /></template>
