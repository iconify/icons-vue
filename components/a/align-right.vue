<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz4f9wtxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pz4f9wtxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:align-right" /></template>
