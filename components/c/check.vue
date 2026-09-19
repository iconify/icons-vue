<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmv704bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zmv704bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:check" /></template>
