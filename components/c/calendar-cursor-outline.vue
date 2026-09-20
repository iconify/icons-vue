<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k76wz3z4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k76wz3z4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-cursor-outline" /></template>
