<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1no9fr_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1no9fr_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:bag-fill" /></template>
