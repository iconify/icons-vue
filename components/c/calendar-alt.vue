<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_1hckbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s_1hckbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:calendar-alt" /></template>
