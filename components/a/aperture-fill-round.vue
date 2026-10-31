<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2dpobuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij2dpobuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aperture-fill-round" /></template>
