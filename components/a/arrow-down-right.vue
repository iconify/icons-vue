<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymkz3sb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ymkz3sb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down-right" /></template>
