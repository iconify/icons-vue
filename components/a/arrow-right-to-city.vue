<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7qbhwd3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r7qbhwd3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-right-to-city" /></template>
