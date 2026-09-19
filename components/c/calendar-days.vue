<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0_s5_kbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="n0_s5_kbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-days" /></template>
