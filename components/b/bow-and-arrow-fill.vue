<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utiac6bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="utiac6bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bow-and-arrow-fill" /></template>
