<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhta4sb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhta4sb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-bold" /></template>
