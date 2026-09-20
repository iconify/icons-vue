<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hneyai_ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hneyai_ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:celsius-line" /></template>
