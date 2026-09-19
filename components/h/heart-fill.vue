<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkex97b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pkex97b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:heart-fill" /></template>
