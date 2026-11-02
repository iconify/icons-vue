<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r88b0ccfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r88b0ccfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dashboard-3-line" /></template>
