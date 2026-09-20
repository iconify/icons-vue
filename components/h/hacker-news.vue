<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d55d938rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d55d938rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hacker-news" /></template>
