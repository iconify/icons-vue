<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id7o3weik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id7o3weik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-text-fill-round" /></template>
