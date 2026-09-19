<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s241fub9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s241fub9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:info" /></template>
