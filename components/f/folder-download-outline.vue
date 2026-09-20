<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4_0ubmzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4_0ubmzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-download-outline" /></template>
