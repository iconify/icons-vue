<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0pyh4m-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0pyh4m-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-lock" /></template>
