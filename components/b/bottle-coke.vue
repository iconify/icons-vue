<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9wptzrzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9wptzrzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-coke" /></template>
