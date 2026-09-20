<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi91_ui2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi91_ui2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:fat-corner-left-up" /></template>
