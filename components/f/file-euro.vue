<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f41w83s2w.css';
import '../../css/r/rl4zu8qob.css';
import '../../css/e/ehx0rebpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f41w83s2w"/><path class="rl4zu8qob"/><path class="ehx0rebpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-euro" /></template>
