<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwcjaq9ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwcjaq9ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-check-solid" /></template>
