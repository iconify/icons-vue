<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn_uo6biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vn_uo6biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:calendar-number" /></template>
