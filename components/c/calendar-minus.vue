<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn_3ohb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yn_3ohb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-minus" /></template>
