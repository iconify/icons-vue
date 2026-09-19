<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2d48ia-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2d48ia-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hot-meal-24px" /></template>
