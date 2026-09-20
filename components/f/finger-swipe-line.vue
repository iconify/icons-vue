<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irve6l9sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irve6l9sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:finger-swipe-line" /></template>
