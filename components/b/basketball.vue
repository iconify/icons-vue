<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvn7yqk5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lvn7yqk5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:basketball" /></template>
