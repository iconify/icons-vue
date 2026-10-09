<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9is0ybwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y9is0ybwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-rain-48-bold" /></template>
