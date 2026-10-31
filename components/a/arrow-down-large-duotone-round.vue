<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhxdvy5ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhxdvy5ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-large-duotone-round" /></template>
