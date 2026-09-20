<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp-esvb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp-esvb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:briefcase-account" /></template>
