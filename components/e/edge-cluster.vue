<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quskwkuku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="quskwkuku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:edge-cluster" /></template>
