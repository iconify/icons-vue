<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewzv9gbuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewzv9gbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-outer-dashed-circle" /></template>
