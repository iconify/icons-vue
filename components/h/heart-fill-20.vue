<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx63x44ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rx63x44ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:heart-fill-20" /></template>
