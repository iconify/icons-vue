<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpadxjbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cpadxjbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-bold-text-bold-formatting-format" /></template>
