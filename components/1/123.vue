<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqvd6z70p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqvd6z70p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:123" /></template>
