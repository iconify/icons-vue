<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hioldmbfk.css';
import '../../css/d/d0k502nsw.css';
import '../../css/e/efb3h0bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hioldmbfk"/><path class="d0k502nsw"/><path class="efb3h0bra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balloon-broken" /></template>
