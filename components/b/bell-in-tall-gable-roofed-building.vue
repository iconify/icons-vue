<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvdl01b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zvdl01b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bell-in-tall-gable-roofed-building" /></template>
