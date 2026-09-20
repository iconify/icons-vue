<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf8jbf8en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf8jbf8en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-export-outline" /></template>
