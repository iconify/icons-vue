<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwfex86-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="cwfex86-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:group" /></template>
