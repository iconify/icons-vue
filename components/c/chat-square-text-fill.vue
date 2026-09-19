<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5e567fow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i5e567fow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-square-text-fill" /></template>
