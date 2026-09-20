<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s16nwnbzm.css';
import '../../css/d/d1nthkbwk.css';
import '../../css/v/v_ibbwbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s16nwnbzm"/><path class="d1nthkbwk"/><path class="v_ibbwbff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:balloon-linear" /></template>
