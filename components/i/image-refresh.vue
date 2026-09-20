<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7tz7yxbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7tz7yxbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-refresh" /></template>
