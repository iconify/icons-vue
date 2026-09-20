<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5mjcbcrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="d5mjcbcrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:dot-octagon-fill" /></template>
