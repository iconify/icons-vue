<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y04p36b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y04p36b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:crosshair-plus-dot" /></template>
