<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f971rbbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f971rbbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ancient-pavilion-line" /></template>
