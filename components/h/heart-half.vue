<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlvkwy0ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlvkwy0ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:heart-half" /></template>
