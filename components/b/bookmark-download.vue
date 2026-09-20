<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i0flq-qyx.css';
import '../../css/v/v6s8134kp.css';
import '../../css/u/ur3jr1b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i0flq-qyx"/><path class="v6s8134kp"/><path class="ur3jr1b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-download" /></template>
