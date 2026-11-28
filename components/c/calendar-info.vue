<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoc0ddcsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoc0ddcsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calendar-info" /></template>
