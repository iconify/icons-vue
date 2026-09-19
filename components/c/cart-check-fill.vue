<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8engob6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y8engob6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cart-check-fill" /></template>
