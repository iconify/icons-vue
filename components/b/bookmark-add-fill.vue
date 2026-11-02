<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_78s8hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1_78s8hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-add-fill" /></template>
