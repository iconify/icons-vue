<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7g0q9y_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y7g0q9y_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:export-failed" /></template>
