<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad6uctxxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ad6uctxxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bcbc" /></template>
