<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7sfh3a7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7sfh3a7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-snooze-solid" /></template>
