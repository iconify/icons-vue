<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glzitecoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glzitecoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-month-line" /></template>
