<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf03oqols.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mf03oqols"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-6" /></template>
