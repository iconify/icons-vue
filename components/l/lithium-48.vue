<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze82bcb9d.css';
import '../../css/s/su1__b-9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ze82bcb9d"/><path class="su1__b-9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lithium-48" /></template>
