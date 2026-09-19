<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/expzhk9as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="expzhk9as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-plus-filled" /></template>
