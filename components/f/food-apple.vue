<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3vo60byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3vo60byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:food-apple" /></template>
