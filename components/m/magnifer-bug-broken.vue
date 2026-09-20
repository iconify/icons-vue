<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ig7l8tpsj.css';
import '../../css/k/kjxg36b_m.css';
import '../../css/x/x09loybdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ig7l8tpsj"/><path class="kjxg36b_m"/><path class="x09loybdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-bug-broken" /></template>
