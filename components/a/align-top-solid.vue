<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln15bwbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln15bwbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:align-top-solid" /></template>
