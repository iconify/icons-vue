<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-q1a4j0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s-q1a4j0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:inbox" /></template>
