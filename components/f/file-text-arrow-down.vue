<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih9a8_b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih9a8_b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-arrow-down" /></template>
