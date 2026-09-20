<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng7wvzb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng7wvzb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:loading-2" /></template>
