<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi_6xzbaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi_6xzbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:funnel" /></template>
