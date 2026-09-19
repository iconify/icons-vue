<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ketm56k_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ketm56k_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:align-right" /></template>
