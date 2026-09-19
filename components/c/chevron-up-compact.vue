<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s92032bsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="s92032bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:chevron-up-compact" /></template>
