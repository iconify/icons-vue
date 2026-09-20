<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvaqon8oy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvaqon8oy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hearts-fill" /></template>
