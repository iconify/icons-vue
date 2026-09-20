<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehwi6-ffd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehwi6-ffd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eraser-fill" /></template>
