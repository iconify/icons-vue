<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s63-c7bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="s63-c7bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-text-formatting-center-align-text-alignment-align-paragraph-centered-formatting-center" /></template>
