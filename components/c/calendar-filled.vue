<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_s3f5bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_s3f5bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:calendar-filled" /></template>
