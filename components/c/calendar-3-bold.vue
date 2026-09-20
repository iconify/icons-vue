<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3_-5u1bi.css';
import '../../css/s/sb5p6obzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3_-5u1bi"/><path class="sb5p6obzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:calendar-3-bold" /></template>
