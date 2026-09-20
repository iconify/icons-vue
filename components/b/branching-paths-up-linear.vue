<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pw8f5c0fp.css';
import '../../css/w/wrqhnubdm.css';
import '../../css/c/c6g87kbzs.css';
import '../../css/n/n7bi59bvp.css';
import '../../css/f/f0le29xkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pw8f5c0fp"/><path class="wrqhnubdm"/><path class="c6g87kbzs"/><path class="n7bi59bvp"/><path class="f0le29xkr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-up-linear" /></template>
