<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oul3lf3aq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="oul3lf3aq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:clipboard" /></template>
