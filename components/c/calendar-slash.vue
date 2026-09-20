<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irsevjb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irsevjb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:calendar-slash" /></template>
