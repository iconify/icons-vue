<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppakfac4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppakfac4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:brain-03" /></template>
