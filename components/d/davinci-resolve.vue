<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv0nhn8nu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cv0nhn8nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:davinci-resolve" /></template>
