<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndi6ggb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndi6ggb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:expand-all-outline" /></template>
