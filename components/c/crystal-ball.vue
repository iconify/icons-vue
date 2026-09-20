<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm5_z2x2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm5_z2x2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:crystal-ball" /></template>
