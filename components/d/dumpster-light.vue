<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j33jp_drd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="j33jp_drd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:dumpster-light" /></template>
