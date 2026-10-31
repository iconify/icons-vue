<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bshp7aczn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bshp7aczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-duotone-round" /></template>
