<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozb6knb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozb6knb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-star-outline" /></template>
