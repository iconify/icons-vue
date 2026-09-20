<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r36w5t33e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r36w5t33e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:d3js-logo-solid" /></template>
