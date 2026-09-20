<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uudoe427q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uudoe427q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-2-line" /></template>
