<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enkhakfvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="enkhakfvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:dot-hexagon" /></template>
