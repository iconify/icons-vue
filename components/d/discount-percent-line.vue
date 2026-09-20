<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkof6pkkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkof6pkkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:discount-percent-line" /></template>
