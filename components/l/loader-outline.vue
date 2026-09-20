<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfv4w8b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfv4w8b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:loader-outline" /></template>
