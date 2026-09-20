<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1o_7ksyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="u1o_7ksyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-paragraph-column-text-alignment-formatting-paragraph-columns-column-two" /></template>
