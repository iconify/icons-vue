<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju_ra8b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju_ra8b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-x" /></template>
