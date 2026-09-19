<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5c7b29av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g5c7b29av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-time-filled" /></template>
