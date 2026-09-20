<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2q536p7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="w2q536p7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-dashed-down-right" /></template>
