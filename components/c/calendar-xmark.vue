<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfym00_ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="nfym00_ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:calendar-xmark" /></template>
