<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2sxbmu3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="e2sxbmu3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:display-alt" /></template>
