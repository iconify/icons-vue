<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk738ub_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pk738ub_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-bottom-light" /></template>
