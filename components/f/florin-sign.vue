<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs31excvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cs31excvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:florin-sign" /></template>
