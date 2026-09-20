<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0oghdcwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v0oghdcwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:comma" /></template>
