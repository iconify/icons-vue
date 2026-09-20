<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykqei9bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykqei9bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:elevator" /></template>
