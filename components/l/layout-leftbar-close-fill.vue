<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg8m7tbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg8m7tbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-leftbar-close-fill" /></template>
