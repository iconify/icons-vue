<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8nap2xtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8nap2xtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-excel-box" /></template>
