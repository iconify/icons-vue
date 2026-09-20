<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhh0kvbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhh0kvbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:calendar" /></template>
