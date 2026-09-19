<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyrrunb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dyrrunb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:clear-selection-mirrored" /></template>
