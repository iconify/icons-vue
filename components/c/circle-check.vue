<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oem5txrch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oem5txrch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:circle-check" /></template>
