<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtn3ihboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wtn3ihboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:gps-device" /></template>
