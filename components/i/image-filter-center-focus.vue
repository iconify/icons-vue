<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivylbb__r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivylbb__r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-filter-center-focus" /></template>
