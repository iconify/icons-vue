<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/co44obc9b.css';
import '../../css/j/ja9kt6k1f.css';
import '../../css/r/r34ddx-ox.css';
import '../../css/p/p43uby7qv.css';
import '../../css/j/jxwmk8mdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="co44obc9b"/><path class="ja9kt6k1f wm-k"/><path class="r34ddx-ox wm-k"/><path class="p43uby7qv wm-k"/><path class="jxwmk8mdu wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-sketch" /></template>
