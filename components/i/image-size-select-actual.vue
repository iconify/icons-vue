<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w747y2bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w747y2bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-size-select-actual" /></template>
