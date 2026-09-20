<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vevfxlbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vevfxlbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:half-1" /></template>
