<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-3xb2--v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-3xb2--v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:low-priority" /></template>
