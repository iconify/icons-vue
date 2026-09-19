<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abbv8_b5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abbv8_b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-bar-square-filled" /></template>
