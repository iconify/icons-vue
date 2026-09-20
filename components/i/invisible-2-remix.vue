<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffrvd0_7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ffrvd0_7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:invisible-2-remix" /></template>
