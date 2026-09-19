<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpvz-r1bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cpvz-r1bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:keyboard-fill" /></template>
