<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwe_2a0ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwe_2a0ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:body-scan-line" /></template>
