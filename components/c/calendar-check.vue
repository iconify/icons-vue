<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3cknw6dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="c3cknw6dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:calendar-check" /></template>
