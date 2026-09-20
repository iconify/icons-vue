<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz6h1pstq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pz6h1pstq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:four-over-water" /></template>
