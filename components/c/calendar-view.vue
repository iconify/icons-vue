<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emmfvjufh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emmfvjufh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-view" /></template>
