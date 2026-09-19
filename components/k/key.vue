<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djvzlmb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="djvzlmb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:key" /></template>
