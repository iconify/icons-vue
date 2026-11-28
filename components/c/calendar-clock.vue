<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhaiqhmbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vhaiqhmbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-clock" /></template>
