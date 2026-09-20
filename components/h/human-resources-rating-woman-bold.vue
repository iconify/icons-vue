<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw0d3xbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw0d3xbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:human-resources-rating-woman-bold" /></template>
