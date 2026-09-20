<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp12kbbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="kp12kbbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:calendar-add" /></template>
