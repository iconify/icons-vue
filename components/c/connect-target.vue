<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3okiijpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j3okiijpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:connect-target" /></template>
