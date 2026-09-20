<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu_1temnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu_1temnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-multiple-fill" /></template>
