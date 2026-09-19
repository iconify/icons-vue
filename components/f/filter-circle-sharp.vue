<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7qde211y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j7qde211y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:filter-circle-sharp" /></template>
