<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kpx6umtca.css';
import '../../css/i/iol7-wboy.css';
import '../../css/h/hx-ne6b0c.css';
import '../../css/o/ourvjgbzk.css';
import '../../css/l/l4vdwdbyo.css';
import '../../css/j/jc8brab-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kpx6umtca"/><path class="iol7-wboy"/><path class="hx-ne6b0c"/><path clip-rule="evenodd" class="ourvjgbzk"/><path class="l4vdwdbyo"/><path class="jc8brab-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:glasses" /></template>
