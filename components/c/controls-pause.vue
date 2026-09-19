<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0i-ett0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d0i-ett0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-pause" /></template>
