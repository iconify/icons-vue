<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o29_ehb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o29_ehb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-clock-bold" /></template>
