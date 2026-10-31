<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llzilzr9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llzilzr9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-fill-round" /></template>
