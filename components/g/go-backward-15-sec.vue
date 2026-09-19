<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dq313mm_u.css';
import '../../css/l/l9gydfb8l.css';
import '../../css/t/t2c-yabxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dq313mm_u"/><path class="l9gydfb8l"/><path class="t2c-yabxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:go-backward-15-sec" /></template>
