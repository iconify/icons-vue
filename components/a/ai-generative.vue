<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8m9hrbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8m9hrbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-generative" /></template>
