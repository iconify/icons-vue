<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p5yua1bwn.css';
import '../../css/t/t5ew0tu8l.css';
import '../../css/h/hpz3uft5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p5yua1bwn"/><path class="t5ew0tu8l"/><path class="hpz3uft5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:drag-left-02" /></template>
