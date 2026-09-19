<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij74tbbef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ij74tbbef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:atlas" /></template>
