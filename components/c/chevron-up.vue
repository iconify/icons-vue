<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3do5x6wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="n3do5x6wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:chevron-up" /></template>
