<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvs2y_6ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hvs2y_6ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-round-up-right" /></template>
