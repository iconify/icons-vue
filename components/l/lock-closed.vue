<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cts_fdbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cts_fdbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:lock-closed" /></template>
