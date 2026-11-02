<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc4hr0b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc4hr0b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-fading-arrow-up-fill" /></template>
