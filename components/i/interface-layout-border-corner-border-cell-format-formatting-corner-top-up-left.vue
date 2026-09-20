<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3tf_jmrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s3tf_jmrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-layout-border-corner-border-cell-format-formatting-corner-top-up-left" /></template>
