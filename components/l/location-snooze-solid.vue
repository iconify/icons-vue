<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws61ilbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws61ilbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-snooze-solid" /></template>
