<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1w4obb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1w4obb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-back-left" /></template>
