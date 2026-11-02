<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqwz1xbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqwz1xbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-line" /></template>
