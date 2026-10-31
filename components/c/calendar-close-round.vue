<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty-5kcb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-5kcb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-close-round" /></template>
