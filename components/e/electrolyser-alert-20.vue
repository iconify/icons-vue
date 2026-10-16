<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o640wlber.css';
import '../../css/w/woh0b19bt.css';
import '../../css/p/puz5jibvr.css';
import '../../css/n/nq5_p_bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o640wlber"/><path class="woh0b19bt"/><path class="puz5jibvr"/><path class="nq5_p_bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electrolyser-alert-20" /></template>
