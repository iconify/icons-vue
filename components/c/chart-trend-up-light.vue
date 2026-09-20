<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhr7z3b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhr7z3b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-trend-up-light" /></template>
