<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1a8l432h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1a8l432h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:infinity-box-outline" /></template>
