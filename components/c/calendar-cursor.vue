<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxh-lfu2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxh-lfu2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-cursor" /></template>
