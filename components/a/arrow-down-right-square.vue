<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1r0tnbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d1r0tnbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-down-right-square" /></template>
