<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu97ff9zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu97ff9zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-lock-open-outline" /></template>
