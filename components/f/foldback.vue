<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1zlwfbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i1zlwfbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:foldback" /></template>
