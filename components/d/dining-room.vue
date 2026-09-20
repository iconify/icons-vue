<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu7afbcqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu7afbcqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dining-room" /></template>
