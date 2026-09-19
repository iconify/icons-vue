<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izxba7fqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izxba7fqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:draw-inside" /></template>
