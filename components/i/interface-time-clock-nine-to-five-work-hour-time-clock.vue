<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7bk3rb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="c7bk3rb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-time-clock-nine-to-five-work-hour-time-clock" /></template>
