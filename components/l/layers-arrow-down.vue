<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivr_rx2lm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivr_rx2lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:layers-arrow-down" /></template>
