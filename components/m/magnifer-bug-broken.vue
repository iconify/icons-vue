<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ig7l8tpsj.css';
import '../../css/x/x09loybdy.css';
import '../../css/o/o3o_tvbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ig7l8tpsj"/><path class="x09loybdy"/><path class="o3o_tvbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-bug-broken" /></template>
