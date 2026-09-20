<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uln5-cbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uln5-cbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-up-right" /></template>
