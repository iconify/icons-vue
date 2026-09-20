<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-4z-bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-4z-bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:device-line" /></template>
