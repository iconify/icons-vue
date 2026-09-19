<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru4zkgb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru4zkgb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:calendar-plus-solid" /></template>
