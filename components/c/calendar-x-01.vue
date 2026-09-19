<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mctm2wb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mctm2wb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:calendar-x-01" /></template>
