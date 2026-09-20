<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re3f74b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="re3f74b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:arrow-down" /></template>
