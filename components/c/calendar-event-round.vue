<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1c_djb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1c_djb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-event-round" /></template>
