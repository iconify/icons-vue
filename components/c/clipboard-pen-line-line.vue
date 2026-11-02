<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igc5pzbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igc5pzbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-pen-line-line" /></template>
