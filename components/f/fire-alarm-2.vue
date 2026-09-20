<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne7-robio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ne7-robio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fire-alarm-2" /></template>
