<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabl9iovh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mabl9iovh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:controls-volumeon" /></template>
