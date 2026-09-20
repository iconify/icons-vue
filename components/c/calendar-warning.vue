<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfsbn6bjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfsbn6bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-warning" /></template>
