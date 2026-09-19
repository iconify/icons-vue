<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa2y9obwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xa2y9obwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:align-right-stroke-12" /></template>
