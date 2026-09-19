<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pssxu37lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pssxu37lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:box" /></template>
