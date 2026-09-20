<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaod-urcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xaod-urcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dishwasher-alert" /></template>
