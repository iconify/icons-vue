<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la4yf5w1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la4yf5w1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:download" /></template>
