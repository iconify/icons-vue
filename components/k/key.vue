<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_-cg7b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":730};
const content = `<path class="e_-cg7b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:key" /></template>
