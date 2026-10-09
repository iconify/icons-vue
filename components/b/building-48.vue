<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htkol23wy.css';
import '../../css/c/c682obb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="htkol23wy"/><path class="c682obb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-48" /></template>
