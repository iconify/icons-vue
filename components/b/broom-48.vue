<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwpkbabou.css';
import '../../css/t/twn6trvue.css';
import '../../css/m/motikac1y.css';
import '../../css/q/qul3hj1lj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwpkbabou"/><path class="twn6trvue"/><path class="motikac1y"/><path class="qul3hj1lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:broom-48" /></template>
