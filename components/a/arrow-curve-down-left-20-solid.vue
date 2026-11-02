<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9he1_b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d9he1_b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-down-left-20-solid" /></template>
