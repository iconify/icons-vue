<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe8s97qji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe8s97qji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-down-right-bold" /></template>
