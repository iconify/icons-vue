<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pao8l1btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="pao8l1btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-right-circle" /></template>
