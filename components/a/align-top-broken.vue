<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qqrohvb8p.css';
import '../../css/i/i9spxybks.css';
import '../../css/c/cts3slb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qqrohvb8p"/><path class="i9spxybks"/><path class="cts3slb-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-broken" /></template>
