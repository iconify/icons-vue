<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltk4xvbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltk4xvbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-down-box" /></template>
