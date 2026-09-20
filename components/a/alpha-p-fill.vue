<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc2up6cvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="bc2up6cvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-p-fill" /></template>
