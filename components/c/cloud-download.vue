<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1nd1yxqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1nd1yxqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-download" /></template>
