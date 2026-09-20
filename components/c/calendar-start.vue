<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvaqw3npv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvaqw3npv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-start" /></template>
