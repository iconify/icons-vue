<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grevcnb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grevcnb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-right-fill" /></template>
