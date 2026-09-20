<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbc358yre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bbc358yre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-calendar-disable-calendar-date-day-delete-disable-month-remove" /></template>
