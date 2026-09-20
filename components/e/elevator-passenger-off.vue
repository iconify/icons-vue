<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3r8h6w8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3r8h6w8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevator-passenger-off" /></template>
