<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nolfx4b0d.css';
import '../../css/y/ys3yk5bwx.css';
import '../../css/l/llaf8kysj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nolfx4b0d"/><path class="ys3yk5bwx"/><path class="llaf8kysj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:brain-broken" /></template>
