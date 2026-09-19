<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbbzv8blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mbbzv8blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:info" /></template>
