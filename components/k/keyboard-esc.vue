<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gis85s77z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gis85s77z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-esc" /></template>
