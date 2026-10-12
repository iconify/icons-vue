<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxy8esbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bxy8esbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exclamation-circle-fill-20" /></template>
