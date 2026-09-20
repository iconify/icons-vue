<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icb3i3bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icb3i3bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-circle" /></template>
