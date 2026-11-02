<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o48qy4bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o48qy4bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-1-line" /></template>
