<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8wby-r8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w8wby-r8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:lemon" /></template>
