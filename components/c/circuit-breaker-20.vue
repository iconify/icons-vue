<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo1eldb9g.css';
import '../../css/s/s6o8xgbyi.css';
import '../../css/t/tcpd3kbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fo1eldb9g"/><path class="s6o8xgbyi"/><path class="tcpd3kbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:circuit-breaker-20" /></template>
