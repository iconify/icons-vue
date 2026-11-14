<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1w__abiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1w__abiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chart" /></template>
