<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saz0lkb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="saz0lkb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-minus" /></template>
