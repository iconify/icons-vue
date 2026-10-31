<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwlfc3bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwlfc3bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-a-fill-round" /></template>
