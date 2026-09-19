<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q1g5s_bga.css';
import '../../css/s/sosv7zf-y.css';
import '../../css/p/pk2ijs5sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q1g5s_bga"/><path class="sosv7zf-y"/><path class="pk2ijs5sj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:inbox-duo" /></template>
