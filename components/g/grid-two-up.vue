<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk7shod1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dk7shod1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:grid-two-up" /></template>
