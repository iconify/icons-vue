<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzjavk1ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mzjavk1ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:check-remix" /></template>
