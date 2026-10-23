<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc14tkbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc14tkbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-grid-circles" /></template>
