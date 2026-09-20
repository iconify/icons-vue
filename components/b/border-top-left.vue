<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-33b3hhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="p-33b3hhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:border-top-left" /></template>
