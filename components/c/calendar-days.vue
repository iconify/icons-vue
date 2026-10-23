<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xml7hobsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xml7hobsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-days" /></template>
