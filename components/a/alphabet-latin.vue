<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu3pacbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu3pacbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-latin" /></template>
