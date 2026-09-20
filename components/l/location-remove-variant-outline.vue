<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6txntpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls6txntpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:location-remove-variant-outline" /></template>
