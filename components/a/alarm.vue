<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0ylf6w5b.css';
import '../../css/r/rt3j0ibnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m0ylf6w5b"/><path class="rt3j0ibnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:alarm" /></template>
