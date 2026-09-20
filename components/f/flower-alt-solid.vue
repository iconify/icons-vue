<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-bjy1bjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k-bjy1bjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flower-alt-solid" /></template>
