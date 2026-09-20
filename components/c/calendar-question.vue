<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9-pb7c_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9-pb7c_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-question" /></template>
