<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rhlpg9bkc.css';
import '../../css/h/hct9igb0o.css';
import '../../css/l/ln504ccwh.css';
import '../../css/b/b_-kbob-o.css';
import '../../css/h/h5rptubpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rhlpg9bkc wm-k"/><path class="hct9igb0o wm-shine"/><path class="ln504ccwh wm-shine"/><path class="b_-kbob-o wm-shine"/><path class="h5rptubpv wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-lunar:book" /></template>
