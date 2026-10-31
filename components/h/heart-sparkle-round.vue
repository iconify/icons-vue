<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao0_fxa0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao0_fxa0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-sparkle-round" /></template>
