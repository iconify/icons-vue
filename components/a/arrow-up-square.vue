<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5ekv3_nq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g5ekv3_nq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-square" /></template>
