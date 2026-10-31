<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfvj6mbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvj6mbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fish-round" /></template>
