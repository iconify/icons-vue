<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwvf1sbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vwvf1sbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:house-flood-water" /></template>
