<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtuzohpul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rtuzohpul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:bold" /></template>
