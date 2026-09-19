<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1e-a9n7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="x1e-a9n7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:building-circle-exclamation" /></template>
