<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao0h70_1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao0h70_1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-minus" /></template>
