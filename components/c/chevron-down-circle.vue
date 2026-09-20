<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx7iuhb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hx7iuhb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-down-circle" /></template>
