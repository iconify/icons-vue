<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcjif3b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcjif3b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:indent-duotone-round" /></template>
