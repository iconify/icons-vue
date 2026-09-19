<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8f4job8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="p8f4job8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:calendar-work-week" /></template>
