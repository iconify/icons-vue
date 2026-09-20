<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/til6eg8hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="til6eg8hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:content-clipboard" /></template>
