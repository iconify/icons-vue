<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf5t8vb8e.css';
import '../../css/o/ofn7d5bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pf5t8vb8e"/><path class="ofn7d5bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:building-real-eastate-storage" /></template>
