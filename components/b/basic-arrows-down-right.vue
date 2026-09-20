<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s52z4mbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s52z4mbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-arrows-down-right" /></template>
