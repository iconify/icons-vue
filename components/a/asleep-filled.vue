<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkrqowbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vkrqowbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:asleep-filled" /></template>
