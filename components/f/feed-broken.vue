<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/exetrlbof.css';
import '../../css/g/g8dwmbbzj.css';
import '../../css/u/uzjqjlk8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="exetrlbof"/><path class="g8dwmbbzj"/><path class="uzjqjlk8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:feed-broken" /></template>
