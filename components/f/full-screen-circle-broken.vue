<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nerijcc5y.css';
import '../../css/g/gqca22zsx.css';
import '../../css/f/f69dim7yf.css';
import '../../css/k/k1rt0cbye.css';
import '../../css/k/ko6o-6b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nerijcc5y"/><path class="gqca22zsx"/><path class="f69dim7yf"/><path class="k1rt0cbye"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:full-screen-circle-broken" /></template>
