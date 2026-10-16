<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjzh0acdq.css';
import '../../css/x/xj3pm5bqn.css';
import '../../css/c/ccxgjdu-m.css';
import '../../css/t/tz2duac5o.css';
import '../../css/w/w3qsn0byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjzh0acdq"/><path class="xj3pm5bqn"/><path class="ccxgjdu-m"/><path class="tz2duac5o"/><path class="w3qsn0byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:enhanced-weathering-48-bold" /></template>
