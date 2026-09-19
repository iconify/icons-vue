<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/as2iwumwv.css';
import '../../css/k/kwzcfwb6x.css';
import '../../css/p/petp2dagr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="as2iwumwv"/><path class="kwzcfwb6x"/><path class="petp2dagr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:coral" /></template>
