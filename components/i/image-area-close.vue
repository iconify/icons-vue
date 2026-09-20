<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnv-7sb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnv-7sb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-area-close" /></template>
