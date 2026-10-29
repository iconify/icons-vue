<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue075dbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue075dbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-chevrons-right" /></template>
