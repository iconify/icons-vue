<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/say8_yggr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="say8_yggr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ion" /></template>
