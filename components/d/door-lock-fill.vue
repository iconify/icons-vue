<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2h2y-e_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2h2y-e_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-lock-fill" /></template>
