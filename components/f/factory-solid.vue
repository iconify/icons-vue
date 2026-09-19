<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu9mk0bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bu9mk0bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:factory-solid" /></template>
