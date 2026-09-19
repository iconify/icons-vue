<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0zz0d6cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f0zz0d6cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:forward" /></template>
