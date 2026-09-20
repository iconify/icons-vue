<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvn9to28b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="kvn9to28b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:coin-silver" /></template>
