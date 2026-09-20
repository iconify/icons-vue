<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd_p_hbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd_p_hbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:calendar-2-sharp" /></template>
