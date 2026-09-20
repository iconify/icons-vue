<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_rximb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_rximb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:calendar-line" /></template>
