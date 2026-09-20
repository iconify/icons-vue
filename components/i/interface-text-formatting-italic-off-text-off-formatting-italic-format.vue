<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsthl7beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rsthl7beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-italic-off-text-off-formatting-italic-format" /></template>
