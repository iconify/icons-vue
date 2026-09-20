<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9kspab5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9kspab5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-remove-outline" /></template>
