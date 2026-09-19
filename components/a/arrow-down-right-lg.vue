<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbwfv4bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbwfv4bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-down-right-lg" /></template>
