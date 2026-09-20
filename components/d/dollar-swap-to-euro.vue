<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1qs6fb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h1qs6fb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dollar-swap-to-euro" /></template>
