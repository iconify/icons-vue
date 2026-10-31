<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4h-lfodh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4h-lfodh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-dashed-check-duotone-round" /></template>
