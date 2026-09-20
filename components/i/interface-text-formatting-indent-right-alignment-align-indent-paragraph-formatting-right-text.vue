<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqwid4b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sqwid4b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-indent-right-alignment-align-indent-paragraph-formatting-right-text" /></template>
