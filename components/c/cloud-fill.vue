<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoaqcj3qz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoaqcj3qz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cloud-fill" /></template>
