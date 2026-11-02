<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aocoi0bwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aocoi0bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-justify-center-line" /></template>
