<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azlb28tvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azlb28tvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:gauge" /></template>
