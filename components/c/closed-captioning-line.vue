<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkea7ab3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tkea7ab3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:closed-captioning-line" /></template>
