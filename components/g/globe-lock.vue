<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0cx09bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0cx09bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:globe-lock" /></template>
