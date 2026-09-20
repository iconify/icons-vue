<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzy313b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzy313b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-grid-fill" /></template>
