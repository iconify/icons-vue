<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kngbd3brn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kngbd3brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:airplane" /></template>
