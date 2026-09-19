<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co_pena6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="co_pena6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-color-fill" /></template>
