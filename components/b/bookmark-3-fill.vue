<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izhxi_b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izhxi_b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bookmark-3-fill" /></template>
