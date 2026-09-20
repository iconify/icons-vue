<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wma8swbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wma8swbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-s-fill" /></template>
