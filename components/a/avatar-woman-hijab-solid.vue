<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijxlat0tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijxlat0tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-hijab-solid" /></template>
