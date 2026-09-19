<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy9emkllg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="sy9emkllg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calendar-day" /></template>
