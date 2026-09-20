<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9o022b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c9o022b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:car-taxi-1-solid" /></template>
