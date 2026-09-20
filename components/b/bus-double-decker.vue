<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4w5y8boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4w5y8boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bus-double-decker" /></template>
