<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1d8ujg_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="a1d8ujg_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:alpha-c" /></template>
