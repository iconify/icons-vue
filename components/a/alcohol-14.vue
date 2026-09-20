<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu0cucc-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="bu0cucc-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:alcohol-14" /></template>
