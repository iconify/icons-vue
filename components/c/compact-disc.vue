<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi9j9ccge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vi9j9ccge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:compact-disc" /></template>
