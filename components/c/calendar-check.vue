<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_xvtz4fm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="i_xvtz4fm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:calendar-check" /></template>
