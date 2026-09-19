<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do-zxyb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="do-zxyb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:fullscreen-exit-alt" /></template>
