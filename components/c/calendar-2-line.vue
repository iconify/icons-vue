<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htxsu-e7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htxsu-e7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:calendar-2-line" /></template>
