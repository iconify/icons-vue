<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdv_6bbog.css';
import '../../css/i/iz2obhzwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mdv_6bbog"/><path class="iz2obhzwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calendar-add" /></template>
