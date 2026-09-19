<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th6-23bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="th6-23bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:calendar-alt" /></template>
