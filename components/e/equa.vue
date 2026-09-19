<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_1hf_bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k_1hf_bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:equa" /></template>
