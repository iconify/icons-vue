<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7q32y5jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v7q32y5jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:flash-1-solid" /></template>
