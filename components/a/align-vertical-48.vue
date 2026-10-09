<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia5lbtbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia5lbtbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-vertical-48" /></template>
