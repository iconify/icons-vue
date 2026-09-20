<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdexnxz5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdexnxz5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:auto-box" /></template>
