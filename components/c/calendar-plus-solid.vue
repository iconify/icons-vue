<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db-202bme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="db-202bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:calendar-plus-solid" /></template>
