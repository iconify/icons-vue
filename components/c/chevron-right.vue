<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubbzq5eml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":160,"height":384};
const content = `<path class="ubbzq5eml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:chevron-right" /></template>
