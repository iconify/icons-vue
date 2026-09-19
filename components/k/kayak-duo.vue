<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qjf9cqe6j.css';
import '../../css/i/i60x8hbxx.css';
import '../../css/f/f0ff_--3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qjf9cqe6j"/><path class="i60x8hbxx"/><path class="f0ff_--3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:kayak-duo" /></template>
