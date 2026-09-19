<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cmps53bym.css';
import '../../css/y/y044atteb.css';
import '../../css/t/t9f0nvdqy.css';
import '../../css/q/q4hhm4b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cmps53bym"/><path class="y044atteb"/><path class="t9f0nvdqy"/><path class="q4hhm4b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:locked-book" /></template>
