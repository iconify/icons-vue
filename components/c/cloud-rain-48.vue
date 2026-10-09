<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a21vn_b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a21vn_b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-rain-48" /></template>
