<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yco4--zyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yco4--zyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-floor-attic" /></template>
