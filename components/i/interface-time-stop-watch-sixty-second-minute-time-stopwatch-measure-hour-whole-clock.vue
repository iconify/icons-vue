<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkuni3b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xkuni3b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-stop-watch-sixty-second-minute-time-stopwatch-measure-hour-whole-clock" /></template>
