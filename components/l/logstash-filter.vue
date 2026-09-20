<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi9tzv3au.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wi9tzv3au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:logstash-filter" /></template>
