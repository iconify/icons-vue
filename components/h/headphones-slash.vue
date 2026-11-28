<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-mr8_b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x-mr8_b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:headphones-slash" /></template>
