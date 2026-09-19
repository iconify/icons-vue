<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0yx3epbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m0yx3epbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:caret-up-square-fill" /></template>
