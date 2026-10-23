<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyi59vbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyi59vbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-chevrons-left" /></template>
