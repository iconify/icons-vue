<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzkuv1b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzkuv1b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell-snooze-solid" /></template>
