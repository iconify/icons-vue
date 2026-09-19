<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-8v7zbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x-8v7zbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-world-outline" /></template>
