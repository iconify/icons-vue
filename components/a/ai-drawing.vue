<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egl6-waod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egl6-waod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-drawing" /></template>
