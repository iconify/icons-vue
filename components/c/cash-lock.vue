<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8iw44bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8iw44bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-lock" /></template>
