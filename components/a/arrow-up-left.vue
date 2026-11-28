<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlw8gbbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlw8gbbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-up-left" /></template>
