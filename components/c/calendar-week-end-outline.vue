<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9l2cibtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9l2cibtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-week-end-outline" /></template>
