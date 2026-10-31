<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziz0u5bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziz0u5bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-sparkle-round" /></template>
