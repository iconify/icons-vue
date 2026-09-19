<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe6v-xfxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pe6v-xfxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:corn" /></template>
