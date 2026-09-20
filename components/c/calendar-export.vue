<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwa8e7bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwa8e7bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-export" /></template>
