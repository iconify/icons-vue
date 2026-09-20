<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwl4a6cod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwl4a6cod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-circle" /></template>
