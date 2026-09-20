<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og-vwh8xj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="og-vwh8xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:input-box-solid" /></template>
