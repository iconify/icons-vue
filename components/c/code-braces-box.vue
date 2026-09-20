<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7qpof6pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7qpof6pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-braces-box" /></template>
