<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ri3ffybak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ri3ffybak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:clipboard-check" /></template>
