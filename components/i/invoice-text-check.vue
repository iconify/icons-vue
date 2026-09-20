<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvn8gabrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvn8gabrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-text-check" /></template>
