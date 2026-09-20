<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twwjopbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twwjopbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-close-fill" /></template>
