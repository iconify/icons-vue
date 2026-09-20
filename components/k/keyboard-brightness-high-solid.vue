<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1o21_0yf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1o21_0yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:keyboard-brightness-high-solid" /></template>
