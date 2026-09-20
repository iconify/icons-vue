<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6k178ekp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6k178ekp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chatbot" /></template>
