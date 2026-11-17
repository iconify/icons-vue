<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr5yr2buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr5yr2buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:chevrons-to-axis-dashed-vertical" /></template>
