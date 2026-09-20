<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe3omq5yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe3omq5yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:disk-alert" /></template>
