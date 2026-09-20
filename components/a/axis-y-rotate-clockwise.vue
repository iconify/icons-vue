<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suw_391zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="suw_391zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-y-rotate-clockwise" /></template>
