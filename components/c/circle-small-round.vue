<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d91f4wzgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d91f4wzgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-small-round" /></template>
