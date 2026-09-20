<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt74h2cwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt74h2cwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-plus" /></template>
