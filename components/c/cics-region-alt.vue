<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu7m3979e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wu7m3979e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cics-region-alt" /></template>
