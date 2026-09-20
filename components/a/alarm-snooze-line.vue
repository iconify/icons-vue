<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5taks1bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5taks1bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:alarm-snooze-line" /></template>
