<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljuszjqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aljuszjqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-clock-minus" /></template>
