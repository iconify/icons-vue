<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvokzab5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fvokzab5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:capsule-pill" /></template>
