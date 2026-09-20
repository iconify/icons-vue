<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l__hojbyl.css';
import '../../css/h/hrxhp9b1x.css';
import '../../css/d/d6mqo8bss.css';
import '../../css/q/qp9ttxbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l__hojbyl"/><path class="hrxhp9b1x"/><path class="d6mqo8bss"/><path class="qp9ttxbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firebase" /></template>
