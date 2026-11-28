<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlwjky5aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwjky5aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-column-decreasing-solid" /></template>
