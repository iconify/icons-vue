<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xukn4qufr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xukn4qufr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-midnight-whole-midnight-hour-clock-time" /></template>
