<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wncevmksb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wncevmksb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-box" /></template>
