<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0r7ue6-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0r7ue6-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:feather" /></template>
