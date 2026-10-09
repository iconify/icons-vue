<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9czz4bal.css';
import '../../css/m/m1-j5hxxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d9czz4bal"/><path class="m1-j5hxxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heart-48" /></template>
