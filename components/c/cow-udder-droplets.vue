<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf73r1lpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf73r1lpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:cow-udder-droplets" /></template>
