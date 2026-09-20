<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrgp7_b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hrgp7_b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:camper-trailer" /></template>
