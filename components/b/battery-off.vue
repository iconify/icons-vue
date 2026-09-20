<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we1v6ccdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we1v6ccdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-off" /></template>
