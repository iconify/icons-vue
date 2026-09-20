<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xijjq8bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xijjq8bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-arrow-right" /></template>
