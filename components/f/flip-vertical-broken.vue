<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j28ky6bwi.css';
import '../../css/i/iycceebvi.css';
import '../../css/r/rtt-63oek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j28ky6bwi"/><path class="iycceebvi"/><path class="rtt-63oek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-broken" /></template>
