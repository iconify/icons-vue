<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti3jsoj7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti3jsoj7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:land-plot-fill" /></template>
