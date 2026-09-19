<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp1z_cgza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fp1z_cgza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:calendar-alt" /></template>
