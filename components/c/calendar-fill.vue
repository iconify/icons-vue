<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8qdy_t-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8qdy_t-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-fill" /></template>
