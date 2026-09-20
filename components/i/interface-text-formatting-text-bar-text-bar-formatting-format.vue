<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vokuk34lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vokuk34lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-text-bar-text-bar-formatting-format" /></template>
