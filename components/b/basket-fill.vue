<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcp-q-fmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zcp-q-fmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:basket-fill" /></template>
