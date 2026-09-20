<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbr8r1bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbr8r1bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:expand-horizontal-line" /></template>
