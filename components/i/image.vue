<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybl9i-bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ybl9i-bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:image" /></template>
