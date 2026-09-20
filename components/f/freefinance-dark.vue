<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvmv32bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mvmv32bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freefinance-dark" /></template>
