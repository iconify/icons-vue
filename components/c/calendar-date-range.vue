<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgj0nj_cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj0nj_cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-date-range" /></template>
