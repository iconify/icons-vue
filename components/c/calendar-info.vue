<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6lfp1icm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6lfp1icm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-info" /></template>
