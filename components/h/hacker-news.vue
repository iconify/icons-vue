<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axti0sr1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="axti0sr1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hacker-news" /></template>
