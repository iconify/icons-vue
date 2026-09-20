<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpzo9b7op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kpzo9b7op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:humidity-none" /></template>
