<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxk1d8bpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxk1d8bpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:confetti-solid" /></template>
