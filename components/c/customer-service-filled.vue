<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8st50b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s8st50b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:customer-service-filled" /></template>
