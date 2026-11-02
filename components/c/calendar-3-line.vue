<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0cr4vzca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0cr4vzca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-3-line" /></template>
