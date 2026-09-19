<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6l8pobbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="v6l8pobbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-plus" /></template>
