<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj2hj6ivg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yj2hj6ivg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-clock" /></template>
