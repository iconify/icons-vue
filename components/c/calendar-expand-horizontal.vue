<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhxa1bb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhxa1bb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-expand-horizontal" /></template>
