<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvrv9g41e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvrv9g41e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-to-line-duotone-round" /></template>
