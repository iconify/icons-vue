<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iomt7boyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iomt7boyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-lira-2-line" /></template>
