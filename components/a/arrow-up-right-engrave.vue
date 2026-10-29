<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g7jnqr6_z.css';
import '../../css/q/q8e5v33pe.css';
import '../../css/w/wwcy8kijr.css';
import '../../css/b/bu_4u5a3q.css';
import '../../css/k/khppcmayv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g7jnqr6_z wm-k"/><path class="q8e5v33pe wm-a"/><path class="wm-shadow wwcy8kijr"/><path class="bu_4u5a3q wm-k"/><path class="khppcmayv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-up-right-engrave" /></template>
