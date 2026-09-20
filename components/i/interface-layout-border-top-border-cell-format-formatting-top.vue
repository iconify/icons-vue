<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh-axobrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oh-axobrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-layout-border-top-border-cell-format-formatting-top" /></template>
