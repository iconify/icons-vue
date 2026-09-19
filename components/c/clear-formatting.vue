<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi3p-9b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi3p-9b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:clear-formatting" /></template>
