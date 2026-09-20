<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5y8o05ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5y8o05ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevron-left" /></template>
