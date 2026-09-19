<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb3_kbcqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb3_kbcqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar" /></template>
