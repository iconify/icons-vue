<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a1az-nbrd.css';
import '../../css/e/e5hgosb1a.css';
import '../../css/r/rsg6slfkl.css';
import '../../css/j/ja-v4qbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="a1az-nbrd"/><path class="e5hgosb1a"/><path class="rsg6slfkl"/><path class="ja-v4qbal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crosshairs-duo" /></template>
