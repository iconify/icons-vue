<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx3xriblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx3xriblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eigenfocus-dark" /></template>
