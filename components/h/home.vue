<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6r7svz_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t6r7svz_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:home" /></template>
