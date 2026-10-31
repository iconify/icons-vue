<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd8w5db4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd8w5db4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-round" /></template>
