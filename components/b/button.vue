<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_8dtnn9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e_8dtnn9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:button" /></template>
