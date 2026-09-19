<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyf64obgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kyf64obgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gopuram" /></template>
