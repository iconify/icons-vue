<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4n53p-eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4n53p-eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:droplet-half" /></template>
