<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh5gyzgmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh5gyzgmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calendar-3-filled" /></template>
