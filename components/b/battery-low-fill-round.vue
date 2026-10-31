<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/flw1gabej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flw1gabej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-low-fill-round" /></template>
