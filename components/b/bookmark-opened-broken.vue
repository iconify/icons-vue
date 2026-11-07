<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f5hn4upfu.css';
import '../../css/n/nkncs4b1r.css';
import '../../css/o/ollsq1blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f5hn4upfu"/><path class="nkncs4b1r"/><path class="ollsq1blz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-opened-broken" /></template>
