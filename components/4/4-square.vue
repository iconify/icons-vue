<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze0oxb4me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ze0oxb4me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:4-square" /></template>
