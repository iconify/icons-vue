<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew_fwsbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ew_fwsbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:compass-navigator-solid" /></template>
