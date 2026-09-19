<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qug9kx8mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qug9kx8mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:basket" /></template>
