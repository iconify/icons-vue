<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0my8sb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0my8sb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:grimace" /></template>
