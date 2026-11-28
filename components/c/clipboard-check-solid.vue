<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy21efbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy21efbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clipboard-check-solid" /></template>
