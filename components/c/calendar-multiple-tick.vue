<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ght-npoxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ght-npoxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-multiple-tick" /></template>
