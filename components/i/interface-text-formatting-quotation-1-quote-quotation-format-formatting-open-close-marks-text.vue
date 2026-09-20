<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpq5tdlys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wpq5tdlys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-quotation-1-quote-quotation-format-formatting-open-close-marks-text" /></template>
