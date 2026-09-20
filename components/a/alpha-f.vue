<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euyomrbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="euyomrbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-f" /></template>
