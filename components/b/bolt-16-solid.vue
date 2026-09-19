<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlx8kijip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nlx8kijip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bolt-16-solid" /></template>
