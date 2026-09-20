<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r07pcme2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r07pcme2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-left-short-sharp-fill" /></template>
