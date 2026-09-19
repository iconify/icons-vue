<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/phqllkbbt.css';
import '../../css/y/yp4dgwzus.css';
import '../../css/r/rl4zu8qob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="phqllkbbt"/><path class="yp4dgwzus"/><path class="rl4zu8qob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-bitcoin" /></template>
