<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvkbhebit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":386,"height":390};
const content = `<path clip-rule="evenodd" class="cvkbhebit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:goil-dark" /></template>
