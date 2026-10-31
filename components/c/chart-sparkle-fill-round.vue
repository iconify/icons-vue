<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-4ttbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou-4ttbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-sparkle-fill-round" /></template>
