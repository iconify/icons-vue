<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp7ufvbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cp7ufvbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:deno" /></template>
