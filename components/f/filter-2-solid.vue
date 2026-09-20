<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etic5kuwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etic5kuwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:filter-2-solid" /></template>
