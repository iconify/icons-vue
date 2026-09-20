<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2i9qkbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2i9qkbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:infinity" /></template>
