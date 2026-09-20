<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utq87upmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utq87upmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:firebase-line" /></template>
