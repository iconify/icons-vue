<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-jjn8czh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q-jjn8czh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:calendar-pencil-thin" /></template>
