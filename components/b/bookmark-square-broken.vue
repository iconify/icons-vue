<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fs-irwhmz.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/e/e9rq2vbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fs-irwhmz"/><path class="si_mtzbvj"/><path class="e9rq2vbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-square-broken" /></template>
