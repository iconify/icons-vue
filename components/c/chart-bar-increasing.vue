<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/u/usg3cfh9t.css';
import '../../css/r/r7uws0-lq.css';
import '../../css/f/f0g3g2bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="usg3cfh9t wm-shadow"/><path class="r7uws0-lq wm-shadow"/><path class="f0g3g2bxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chart-bar-increasing" /></template>
