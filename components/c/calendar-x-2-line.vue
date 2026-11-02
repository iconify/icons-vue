<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0d0rwa6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0d0rwa6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-x-2-line" /></template>
