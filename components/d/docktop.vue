<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpz8nccen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wpz8nccen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:docktop" /></template>
