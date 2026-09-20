<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/norsy3a8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="norsy3a8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hacker-news-square" /></template>
