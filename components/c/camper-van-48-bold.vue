<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9s80l5jq.css';
import '../../css/o/o244yobqh.css';
import '../../css/g/gezrq7_ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o9s80l5jq"/><path class="o244yobqh"/><path class="gezrq7_ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:camper-van-48-bold" /></template>
