<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6kottvkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6kottvkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gesture-swipe" /></template>
