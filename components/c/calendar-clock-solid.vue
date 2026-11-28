<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwzz-ps3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwzz-ps3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:calendar-clock-solid" /></template>
