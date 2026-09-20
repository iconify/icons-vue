<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh56m7awr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fh56m7awr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-pause" /></template>
