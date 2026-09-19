<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-0mx1beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1856,"height":1536};
const content = `<path class="e-0mx1beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:ambulance" /></template>
